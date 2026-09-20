<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi2dohgdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi2dohgdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:patreon-logo-block" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdz5pm-xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdz5pm-xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:reason-studios-logo-block" {...props}></Icon>

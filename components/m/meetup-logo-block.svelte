<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf4nzsadg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf4nzsadg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:meetup-logo-block" {...props}></Icon>

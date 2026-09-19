<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/d/dc6nqvbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="dc6nqvbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:radio-button-on-outline" {...props}></Icon>

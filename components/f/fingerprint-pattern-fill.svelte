<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htwcbkbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htwcbkbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fingerprint-pattern-fill" {...props}></Icon>

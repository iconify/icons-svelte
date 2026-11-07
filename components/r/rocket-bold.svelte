<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ywg7b9f.css';
import '../../css/r/rcgsjubiv.css';
import '../../css/y/ym8wn7bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ywg7b9f"/><path class="rcgsjubiv"/><path clip-rule="evenodd" class="ym8wn7bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-bold" {...props}></Icon>

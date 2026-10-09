<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otprnqk6j.css';
import '../../css/j/ja-z-qbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="otprnqk6j"/><path class="ja-z-qbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:edit-20" {...props}></Icon>

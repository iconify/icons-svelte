<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcu9xnbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dcu9xnbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlei" {...props}></Icon>

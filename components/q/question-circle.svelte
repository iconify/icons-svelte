<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qund_1b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qund_1b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:question-circle" {...props}></Icon>

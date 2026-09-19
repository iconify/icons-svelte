<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3yeq3__n.css';
import '../../css/q/qbtyf7buh.css';
import '../../css/j/j7hpihb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y3yeq3__n"/><path class="qbtyf7buh"/><path class="j7hpihb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drone-delivery" {...props}></Icon>

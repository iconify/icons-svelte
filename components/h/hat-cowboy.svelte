<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1nvt7bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c1nvt7bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hat-cowboy" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7v6ehbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="o7v6ehbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minismile" {...props}></Icon>

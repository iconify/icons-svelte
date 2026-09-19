<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo8rj3gpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qo8rj3gpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:monitor-26" {...props}></Icon>

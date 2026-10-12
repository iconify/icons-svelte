<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyc9a_bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qyc9a_bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-bullet-20" {...props}></Icon>

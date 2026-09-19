<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmwkbjbqp.css';
import '../../css/s/srynd7nof.css';
import '../../css/e/eq5e06oyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jmwkbjbqp"/><path class="srynd7nof"/><path class="eq5e06oyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-direct-link-1-connect" {...props}></Icon>

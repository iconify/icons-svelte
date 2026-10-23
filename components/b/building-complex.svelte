<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o981pybxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o981pybxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:building-complex" {...props}></Icon>

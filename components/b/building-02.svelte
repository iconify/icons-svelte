<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n22q7k0rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n22q7k0rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:building-02" {...props}></Icon>

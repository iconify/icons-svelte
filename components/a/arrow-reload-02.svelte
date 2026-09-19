<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whpitybyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whpitybyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-reload-02" {...props}></Icon>

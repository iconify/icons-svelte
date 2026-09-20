<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq2_jyb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq2_jyb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:refined-github" {...props}></Icon>

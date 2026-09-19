<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvtehdb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvtehdb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-right" {...props}></Icon>

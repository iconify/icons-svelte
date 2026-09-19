<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-8dv_bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="y-8dv_bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:beeralt" {...props}></Icon>

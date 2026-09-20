<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1bq_0bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1bq_0bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-swiss-franc-fill" {...props}></Icon>

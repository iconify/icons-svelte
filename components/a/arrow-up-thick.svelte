<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6aucrb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6aucrb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-up-thick" {...props}></Icon>

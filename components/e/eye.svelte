<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lemmn_d7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lemmn_d7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:eye" {...props}></Icon>

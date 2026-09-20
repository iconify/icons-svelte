<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lflfbtdmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lflfbtdmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:divide-solid" {...props}></Icon>

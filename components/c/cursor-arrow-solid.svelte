<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_zhm2ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_zhm2ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cursor-arrow-solid" {...props}></Icon>

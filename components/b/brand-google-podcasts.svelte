<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-5e8sbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-5e8sbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-google-podcasts" {...props}></Icon>

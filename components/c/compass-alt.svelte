<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2ykngb7r.css';
import '../../css/b/brphuvboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w2ykngb7r"/><path class="brphuvboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:compass-alt" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ky4jnzf.css';
import '../../css/j/jlozx9b3a.css';
import '../../css/w/wdip6sk2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="s3ky4jnzf"/><path class="jlozx9b3a"/><path class="wdip6sk2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingvin-share-x" {...props}></Icon>

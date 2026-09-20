<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_sn15ygy.css';
import '../../css/s/sq7yslbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_sn15ygy"/><path class="sq7yslbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:material-for-mkdocs-dark" {...props}></Icon>

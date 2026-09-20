<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s06hljcsa.css';
import '../../css/b/b4hqx5wjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s06hljcsa"/><path class="b4hqx5wjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adnanh-webhook" {...props}></Icon>

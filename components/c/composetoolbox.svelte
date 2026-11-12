<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywvh2o5os.css';
import '../../css/h/h8b9m8b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywvh2o5os"/><path class="h8b9m8b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composetoolbox" {...props}></Icon>

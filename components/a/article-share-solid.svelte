<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_w_6xb3l.css';
import '../../css/n/njxe4acos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_w_6xb3l"/><path class="njxe4acos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-share-solid" {...props}></Icon>

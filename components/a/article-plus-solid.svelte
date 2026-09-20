<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_w_6xb3l.css';
import '../../css/f/f7n_6objg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_w_6xb3l"/><path class="f7n_6objg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-plus-solid" {...props}></Icon>

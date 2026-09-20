<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/styafgb6l.css';
import '../../css/h/ht6h5ebzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="styafgb6l"/><path clip-rule="evenodd" class="ht6h5ebzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-date-light" {...props}></Icon>

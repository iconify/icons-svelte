<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avl2890wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avl2890wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-open-outline" {...props}></Icon>

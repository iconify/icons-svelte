<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgq-hoi-s.css';
import '../../css/b/bqo7skq6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgq-hoi-s"/><path class="bqo7skq6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-search-filled" {...props}></Icon>

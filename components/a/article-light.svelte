<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6m6l-blr.css';
import '../../css/a/add8fqwim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6m6l-blr"/><path class="add8fqwim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-light" {...props}></Icon>

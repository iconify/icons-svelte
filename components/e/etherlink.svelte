<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxy5hxwwj.css';
import '../../css/b/b-ya-zbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxy5hxwwj"/><path class="b-ya-zbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:etherlink" {...props}></Icon>

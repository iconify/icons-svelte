<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qehc4-_kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qehc4-_kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:list-add-light" {...props}></Icon>

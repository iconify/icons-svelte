<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl9nzzbwz.css';
import '../../css/w/w65rdobqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl9nzzbwz"/><path clip-rule="evenodd" class="w65rdobqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:content-share-duotone" {...props}></Icon>

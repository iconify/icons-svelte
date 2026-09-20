<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7w0m4zb.css';
import '../../css/d/dfm4qxg6q.css';
import '../../css/a/amyi9lblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7w0m4zb"/><path class="dfm4qxg6q"/><path clip-rule="evenodd" class="amyi9lblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:idv" {...props}></Icon>

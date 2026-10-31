<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr8ohcc6r.css';
import '../../css/t/t39v8hihk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jr8ohcc6r"/><path class="t39v8hihk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:indonesia" {...props}></Icon>

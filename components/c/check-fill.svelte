<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyekt5j2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qyekt5j2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:check-fill" {...props}></Icon>

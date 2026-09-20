<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq-a-zw0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq-a-zw0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:medical-folder-remix" {...props}></Icon>

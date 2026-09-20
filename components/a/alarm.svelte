<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz4blbbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz4blbbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm" {...props}></Icon>

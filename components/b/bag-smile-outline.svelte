<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp4pd42li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp4pd42li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-smile-outline" {...props}></Icon>

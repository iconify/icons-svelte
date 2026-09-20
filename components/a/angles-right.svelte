<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txd2f3f6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txd2f3f6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:angles-right" {...props}></Icon>

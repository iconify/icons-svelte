<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ubtkb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ubtkb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-down-small" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5mzpebcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5mzpebcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:infinity-alt" {...props}></Icon>

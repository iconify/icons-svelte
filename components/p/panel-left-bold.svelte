<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn0qq-buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn0qq-buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-bold" {...props}></Icon>

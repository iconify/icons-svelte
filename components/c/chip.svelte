<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiruhx3ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qiruhx3ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chip" {...props}></Icon>

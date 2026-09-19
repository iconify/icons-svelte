<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjxv9lbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjxv9lbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:png-download" {...props}></Icon>

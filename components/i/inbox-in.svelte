<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5py4ziqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5py4ziqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-in" {...props}></Icon>

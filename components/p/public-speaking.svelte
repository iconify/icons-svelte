<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgf-66bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgf-66bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:public-speaking" {...props}></Icon>

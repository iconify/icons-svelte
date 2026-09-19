<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjnciabat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cjnciabat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-new" {...props}></Icon>

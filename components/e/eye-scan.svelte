<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_axdubmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_axdubmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:eye-scan" {...props}></Icon>

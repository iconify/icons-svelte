<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2gv-r6vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2gv-r6vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:maximize-alt-01" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9-u38b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9-u38b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-horizontal-half" {...props}></Icon>

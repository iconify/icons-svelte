<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf22gsbmi.css';
import '../../css/h/hlcjghfxa.css';
import '../../css/q/qyt2qibcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf22gsbmi wm-a"/><path class="hlcjghfxa wm-a"/><path class="qyt2qibcp wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:list-checks" {...props}></Icon>

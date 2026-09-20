<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogs-x9j_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogs-x9j_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mic" {...props}></Icon>

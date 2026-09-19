<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbc8p3xmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbc8p3xmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:phone-horizontal" {...props}></Icon>

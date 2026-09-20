<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf1a2zbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf1a2zbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-remove" {...props}></Icon>

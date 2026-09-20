<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d185acboo.css';
import '../../css/o/o4dhdybxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d185acboo"/><path class="o4dhdybxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:prob" {...props}></Icon>

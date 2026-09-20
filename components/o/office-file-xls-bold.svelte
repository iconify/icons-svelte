<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtl1ki70z.css';
import '../../css/q/qlpyw3puh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtl1ki70z"/><path class="qlpyw3puh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-file-xls-bold" {...props}></Icon>

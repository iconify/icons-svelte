<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6d9bfo-j.css';
import '../../css/e/ezjzxdbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6d9bfo-j"/><path class="ezjzxdbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-spreadsheet" {...props}></Icon>

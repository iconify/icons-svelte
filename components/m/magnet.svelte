<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbtxlg-vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbtxlg-vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:magnet" {...props}></Icon>

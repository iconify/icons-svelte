<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izlg_obuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izlg_obuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-3" {...props}></Icon>

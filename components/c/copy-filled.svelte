<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apx8rdbbn.css';
import '../../css/u/uwmcnls3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apx8rdbbn"/><path class="uwmcnls3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copy-filled" {...props}></Icon>

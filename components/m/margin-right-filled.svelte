<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt94vufyl.css';
import '../../css/e/e_hujhb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt94vufyl"/><rect class="e_hujhb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:margin-right-filled" {...props}></Icon>

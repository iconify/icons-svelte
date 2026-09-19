<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmmy2rb5f.css';
import '../../css/w/wjguqb06b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmy2rb5f"/><path class="wjguqb06b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-up-arrow" {...props}></Icon>

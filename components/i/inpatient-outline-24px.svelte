<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_877gin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ja_877gin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:inpatient-outline-24px" {...props}></Icon>

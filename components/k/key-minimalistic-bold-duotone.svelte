<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3uje9bbo.css';
import '../../css/v/v1qydc12m.css';
import '../../css/e/er-a0qb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3uje9bbo"/><path class="v1qydc12m"/><path class="er-a0qb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-bold-duotone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0fbn4bvv.css';
import '../../css/e/ep7a_f12q.css';
import '../../css/z/zii2occby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0fbn4bvv"/><path class="ep7a_f12q"/><path class="zii2occby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-outline" {...props}></Icon>

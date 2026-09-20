<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lq-4ydbfu.css';
import '../../css/t/tkjktxqan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lq-4ydbfu"/><path class="tkjktxqan"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:rocket-duotone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7wg9bkj.css';
import '../../css/e/enbl2qcxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hu7wg9bkj"/><path clip-rule="evenodd" class="enbl2qcxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cog-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqcdx_jqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqcdx_jqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-question-sharp-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqd2iu2hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eqd2iu2hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-right-left-solid" {...props}></Icon>

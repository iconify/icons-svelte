<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvi_gobnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvi_gobnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lua" {...props}></Icon>

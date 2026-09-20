<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zivg1ubor.css';
import '../../css/o/o9unsp-hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zivg1ubor"/><path clip-rule="evenodd" class="o9unsp-hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-down-fill" {...props}></Icon>

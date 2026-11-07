<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4z7njbqe.css';
import '../../css/c/c4946-17v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4z7njbqe"/><path class="c4946-17v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-type-bold" {...props}></Icon>

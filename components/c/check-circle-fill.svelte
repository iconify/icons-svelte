<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmjvtdbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmjvtdbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-circle-fill" {...props}></Icon>

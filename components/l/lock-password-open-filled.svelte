<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w313eccov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w313eccov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-password-open-filled" {...props}></Icon>

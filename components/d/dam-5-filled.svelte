<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1j1yutiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1j1yutiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-5-filled" {...props}></Icon>

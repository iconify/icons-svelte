<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj8nszb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj8nszb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkbox-checked-solid-expressive" {...props}></Icon>

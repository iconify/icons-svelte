<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onw5m771l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onw5m771l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:info-triangle-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygwxw340a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygwxw340a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:printer" {...props}></Icon>

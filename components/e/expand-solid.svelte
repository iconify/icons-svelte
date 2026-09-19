<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo7i2ob4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo7i2ob4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:expand-solid" {...props}></Icon>

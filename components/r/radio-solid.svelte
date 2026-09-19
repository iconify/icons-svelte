<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovyi6hy6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovyi6hy6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:radio-solid" {...props}></Icon>

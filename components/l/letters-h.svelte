<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5tf-399p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5tf-399p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-h" {...props}></Icon>

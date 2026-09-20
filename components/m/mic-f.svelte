<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3a4tbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="ob3a4tbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mic-f" {...props}></Icon>

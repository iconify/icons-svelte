<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3mjhacsa.css';
import '../../css/o/odewqcbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3mjhacsa"/><path class="odewqcbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:oni" {...props}></Icon>

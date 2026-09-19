<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/robgy6qcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="robgy6qcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bug-ant-solid" {...props}></Icon>

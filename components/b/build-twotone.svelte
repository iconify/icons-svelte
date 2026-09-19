<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy5jeenne.css';
import '../../css/t/tkw3w5bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cy5jeenne"/><path class="tkw3w5bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:build-twotone" {...props}></Icon>

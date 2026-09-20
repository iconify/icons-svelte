<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c920uovqf.css';
import '../../css/o/okq-o-r4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c920uovqf"/><path class="okq-o-r4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-download-fill" {...props}></Icon>

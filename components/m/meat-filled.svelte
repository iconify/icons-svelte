<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thp3xzwhd.css';
import '../../css/e/ez9lk7bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thp3xzwhd"/><path class="ez9lk7bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meat-filled" {...props}></Icon>

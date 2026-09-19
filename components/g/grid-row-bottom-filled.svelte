<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da9mj-b_s.css';
import '../../css/n/neukm1fuz.css';
import '../../css/b/bhbvqjyxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="da9mj-b_s"/><rect class="neukm1fuz"/><rect class="bhbvqjyxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-row-bottom-filled" {...props}></Icon>

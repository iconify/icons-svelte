<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo6-r_b9m.css';
import '../../css/s/sjw8w__rs.css';
import '../../css/c/c_4mldkyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo6-r_b9m"/><path class="sjw8w__rs"/><path class="c_4mldkyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pbx" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/k7ky6prup.css';
import '../../css/z/zjsg5fbvy.css';
import '../../css/e/etjyq4qct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7ky6prup"/><path class="zjsg5fbvy"/><path class="etjyq4qct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:edit" {...props}></Icon>

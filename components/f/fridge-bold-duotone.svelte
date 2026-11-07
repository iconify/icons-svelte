<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjk5al0qp.css';
import '../../css/u/u3fekhbnn.css';
import '../../css/h/hvm7gjbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjk5al0qp"/><path class="u3fekhbnn"/><path class="hvm7gjbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fridge-bold-duotone" {...props}></Icon>

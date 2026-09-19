<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15nc7ykw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v15nc7ykw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-solvinden" {...props}></Icon>

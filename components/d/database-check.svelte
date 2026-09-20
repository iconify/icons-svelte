<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/khvchvbjy.css';
import '../../css/r/rxrul0eko.css';
import '../../css/k/kkh-o2bqv.css';
import '../../css/m/mu7hqhcsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="khvchvbjy"/><path class="rxrul0eko"/><path class="kkh-o2bqv"/><path class="mu7hqhcsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:database-check" {...props}></Icon>
